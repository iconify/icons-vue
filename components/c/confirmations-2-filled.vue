<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy9jjyb9o.css';
import '../../css/j/jvbg5sbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy9jjyb9o"/><path clip-rule="evenodd" class="jvbg5sbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-2-filled" /></template>
