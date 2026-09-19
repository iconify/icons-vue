<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvmieiphp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvmieiphp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coffee" /></template>
