<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fso_kcrdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fso_kcrdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:at-circle" /></template>
