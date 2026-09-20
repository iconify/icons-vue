<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijcvzebzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijcvzebzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beef" /></template>
