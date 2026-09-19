<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz3unxo7b.css';
import '../../css/c/cgvyvxz3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iz3unxo7b"/><path class="cgvyvxz3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-table-reference" /></template>
