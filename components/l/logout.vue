<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acl-8db1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acl-8db1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:logout" /></template>
