<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0stj-z6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0stj-z6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-branch-plus-filled" /></template>
