<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv8it5a_b.css';
import '../../css/g/g82lygpra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8it5a_b"/><path class="g82lygpra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-left-stroke-circle-filled" /></template>
