<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6rou6sao.css';
import '../../css/y/yismpnbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6rou6sao"/><path class="yismpnbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-plus-filled" /></template>
