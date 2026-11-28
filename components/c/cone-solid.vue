<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb40qvjhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb40qvjhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cone-solid" /></template>
