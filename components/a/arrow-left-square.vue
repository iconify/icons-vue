<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to64u9f4k.css';
import '../../css/j/jor-usn7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to64u9f4k"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-square" /></template>
