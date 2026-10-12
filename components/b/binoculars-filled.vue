<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrg2u5bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrg2u5bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:binoculars-filled" /></template>
