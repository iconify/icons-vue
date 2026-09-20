<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykf21lh5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykf21lh5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-filled" /></template>
