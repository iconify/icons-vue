<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1egrjbgw.css';
import '../../css/d/drbq42kov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1egrjbgw"/><path class="drbq42kov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:basket-shopping-3" /></template>
