<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l84cqnb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l84cqnb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:huawei" /></template>
