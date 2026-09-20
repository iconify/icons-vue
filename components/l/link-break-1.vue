<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdh5bcc2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wdh5bcc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:link-break-1" /></template>
