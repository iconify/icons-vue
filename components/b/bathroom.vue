<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fri_krb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fri_krb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bathroom" /></template>
