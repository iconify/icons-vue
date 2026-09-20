<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pztpj7b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pztpj7b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-pull-solid" /></template>
