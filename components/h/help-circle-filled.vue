<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b82ebgbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b82ebgbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-circle-filled" /></template>
