<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjhi3sj6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjhi3sj6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-z-filled" /></template>
