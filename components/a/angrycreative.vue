<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8yq56beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="w8yq56beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:angrycreative" /></template>
