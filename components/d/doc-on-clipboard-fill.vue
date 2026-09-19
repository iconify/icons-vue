<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcfh--ixw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tcfh--ixw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-on-clipboard-fill" /></template>
