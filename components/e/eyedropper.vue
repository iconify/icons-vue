<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5j_ri7jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k5j_ri7jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eyedropper" /></template>
