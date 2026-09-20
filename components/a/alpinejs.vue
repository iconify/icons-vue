<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8716ac_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8716ac_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:alpinejs" /></template>
