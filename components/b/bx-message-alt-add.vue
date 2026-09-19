<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ezhpb5o.css';
import '../../css/c/ch6_fcbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8ezhpb5o"/><path class="ch6_fcbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-alt-add" /></template>
