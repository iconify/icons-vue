<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovln3iu4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovln3iu4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:email-outline" /></template>
