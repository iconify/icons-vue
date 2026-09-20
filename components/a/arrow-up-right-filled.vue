<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6kgg4c6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6kgg4c6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-right-filled" /></template>
