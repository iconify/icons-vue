<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt_t8dbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt_t8dbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:can-filled" /></template>
