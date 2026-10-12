<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaugexbvp.css';
import '../../css/k/k1bhl7bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaugexbvp"/><path clip-rule="evenodd" class="k1bhl7bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-star-filled" /></template>
