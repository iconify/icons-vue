<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btqb3741s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btqb3741s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bounce-right-filled" /></template>
