<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg2-40p8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg2-40p8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-up-solid" /></template>
