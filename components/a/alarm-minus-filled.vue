<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hemtrxb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hemtrxb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alarm-minus-filled" /></template>
