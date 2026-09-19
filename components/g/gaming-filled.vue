<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j65vee0iz.css';
import '../../css/q/qux_2305e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="j65vee0iz"/><path class="qux_2305e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gaming-filled" /></template>
