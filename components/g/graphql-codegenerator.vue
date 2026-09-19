<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsa3t6fnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":393,"height":512};
const content = `<path class="rsa3t6fnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:graphql-codegenerator" /></template>
