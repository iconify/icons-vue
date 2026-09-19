<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqmgg0cqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqmgg0cqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:language" /></template>
