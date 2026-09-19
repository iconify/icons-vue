<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1o5_0ddl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1o5_0ddl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:inbox-out-filled" /></template>
