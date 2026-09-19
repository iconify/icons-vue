<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hutgu3b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hutgu3b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-pull-request-filled" /></template>
