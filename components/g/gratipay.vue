<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3gvyi5tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="b3gvyi5tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gratipay" /></template>
