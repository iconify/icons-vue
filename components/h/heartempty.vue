<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pin8epb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pin8epb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:heartempty" /></template>
