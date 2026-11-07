<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7jv9kugu.css';
import '../../css/n/nk6ny4bnw.css';
import '../../css/o/orj48-biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jv9kugu"/><path clip-rule="evenodd" class="nk6ny4bnw"/><path class="orj48-biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-bold-duotone" /></template>
