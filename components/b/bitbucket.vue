<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a30no-b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a30no-b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bitbucket" /></template>
