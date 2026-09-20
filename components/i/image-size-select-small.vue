<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrw7sibnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrw7sibnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-size-select-small" /></template>
