<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkk5o7gkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkk5o7gkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-i" /></template>
