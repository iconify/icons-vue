<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvnjtkb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nvnjtkb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:dropbox" /></template>
