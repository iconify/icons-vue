<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6s896bnq.css';
import '../../css/b/bur656b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6s896bnq"/><path class="bur656b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:button-solid" /></template>
