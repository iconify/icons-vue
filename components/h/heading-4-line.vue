<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xerf8cb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xerf8cb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-4-line" /></template>
