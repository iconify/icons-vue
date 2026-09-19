<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht6g7kb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ht6g7kb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:inbox-out-alt" /></template>
