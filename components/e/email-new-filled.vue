<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuw8qb5ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vuw8qb5ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-new-filled" /></template>
