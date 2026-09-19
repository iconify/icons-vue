<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq_sz_0cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="jq_sz_0cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:a-upper-case" /></template>
