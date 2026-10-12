<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2huzkbqd.css';
import '../../css/u/uijt22b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2huzkbqd"/><path class="uijt22b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:backpack-filled" /></template>
