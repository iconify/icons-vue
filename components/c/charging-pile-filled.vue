<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4myizbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4myizbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:charging-pile-filled" /></template>
