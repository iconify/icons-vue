<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcr1zdwxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zcr1zdwxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-vmware-alt" /></template>
