<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufm3krb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ufm3krb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:information-circle-16-solid" /></template>
