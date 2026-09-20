<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiq3suo0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="iiq3suo0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:data-management" /></template>
