<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_tkpbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ck_tkpbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ambulance-filled" /></template>
