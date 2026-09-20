<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie4nicb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie4nicb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-charge" /></template>
