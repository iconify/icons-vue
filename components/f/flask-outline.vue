<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-wvqqbgn.css';
import '../../css/k/k6cv4hiap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wvqqbgn"/><path clip-rule="evenodd" class="k6cv4hiap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:flask-outline" /></template>
