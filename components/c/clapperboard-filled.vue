<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stk6y9nje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stk6y9nje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clapperboard-filled" /></template>
