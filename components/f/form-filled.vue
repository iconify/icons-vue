<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sypqwq-0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sypqwq-0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:form-filled" /></template>
