<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aez1enbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aez1enbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book4" /></template>
