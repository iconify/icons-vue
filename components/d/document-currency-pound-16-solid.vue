<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpsi-dbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bpsi-dbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-pound-16-solid" /></template>
