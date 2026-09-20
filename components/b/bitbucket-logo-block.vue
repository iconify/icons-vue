<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9x3kybiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9x3kybiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bitbucket-logo-block" /></template>
