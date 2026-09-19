<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtr5rhb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtr5rhb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:beaker-solid" /></template>
