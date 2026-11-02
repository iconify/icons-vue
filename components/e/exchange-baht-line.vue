<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6f7gj65i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6f7gj65i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-baht-line" /></template>
