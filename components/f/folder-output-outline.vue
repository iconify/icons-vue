<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjgv7_b4e.css';
import '../../css/f/f4kwoxb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjgv7_b4e"/><path class="f4kwoxb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-output-outline" /></template>
