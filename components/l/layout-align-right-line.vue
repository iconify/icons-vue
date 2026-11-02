<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv-5k9uum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv-5k9uum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-align-right-line" /></template>
