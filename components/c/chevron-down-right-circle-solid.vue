<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb0ktbb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0ktbb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-right-circle-solid" /></template>
