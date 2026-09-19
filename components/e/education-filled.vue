<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-m7aobza.css';
import '../../css/f/fldmn0cpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b o-m7aobza"/><path class="b fldmn0cpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:education-filled" /></template>
