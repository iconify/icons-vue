<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55umkfci.css';
import '../../css/n/nfvqnvzcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c55umkfci"/><path clip-rule="evenodd" class="nfvqnvzcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-3-outline" /></template>
