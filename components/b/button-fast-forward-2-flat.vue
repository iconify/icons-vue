<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii0t0frbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii0t0frbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:button-fast-forward-2-flat" /></template>
