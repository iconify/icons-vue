<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9rxwc--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9rxwc--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-e" /></template>
