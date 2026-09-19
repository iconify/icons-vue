<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm1jq5bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1jq5bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:actions" /></template>
