<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfnhi005r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfnhi005r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:loader-sharp" /></template>
