<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anuis4b4o.css';
import '../../css/q/q3g9f9bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="anuis4b4o b"/><path class="b q3g9f9bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:compare-alt-filled" /></template>
