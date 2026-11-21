<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etah7iban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":215.696,"height":215.696,"left":20.152,"top":20.152};
const content = `<path class="etah7iban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:general-translation" /></template>
