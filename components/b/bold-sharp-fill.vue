<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pam7ue5gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pam7ue5gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bold-sharp-fill" /></template>
