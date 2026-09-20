<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st2yjobkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st2yjobkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-file-outline" /></template>
