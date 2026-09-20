<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im63o6nby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im63o6nby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:basecamp-logo-1-solid" /></template>
