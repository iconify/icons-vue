<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq1yx56sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rq1yx56sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-filled" /></template>
