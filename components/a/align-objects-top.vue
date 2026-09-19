<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxwvt3htn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxwvt3htn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-objects-top" /></template>
