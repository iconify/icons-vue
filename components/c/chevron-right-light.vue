<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnr0-ab0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnr0-ab0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-right-light" /></template>
