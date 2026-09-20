<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpidxr41x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kpidxr41x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bug-solid" /></template>
