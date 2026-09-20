<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aovr4abks.css';
import '../../css/o/o8687p-5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aovr4abks"/><path class="o8687p-5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:charging-battery-empty-bold" /></template>
