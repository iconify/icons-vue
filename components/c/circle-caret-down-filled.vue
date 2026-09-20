<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga72qv3aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga72qv3aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-caret-down-filled" /></template>
