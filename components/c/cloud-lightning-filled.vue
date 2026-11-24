<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_mguhhan.css';
import '../../css/z/z5f1labnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_mguhhan"/><path class="z5f1labnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-lightning-filled" /></template>
