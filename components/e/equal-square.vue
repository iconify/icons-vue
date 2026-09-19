<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoix4ob1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uoix4ob1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:equal-square" /></template>
