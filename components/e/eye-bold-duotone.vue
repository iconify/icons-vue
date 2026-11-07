<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noq8vw_6n.css';
import '../../css/k/k7zx50lak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noq8vw_6n"/><path clip-rule="evenodd" class="k7zx50lak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-bold-duotone" /></template>
