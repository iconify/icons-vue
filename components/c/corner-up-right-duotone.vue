<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3j6brbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3j6brbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-up-right-duotone" /></template>
