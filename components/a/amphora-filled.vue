<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcwb7obit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcwb7obit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:amphora-filled" /></template>
