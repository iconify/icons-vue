<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6bc5sa5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gswap" /></template>
<style>
.w6bc5sa5q {
  fill: var(--svg-color--7377d8, #7377d8);
  d: path("m17.906 6.938l.563-2.25H8.625c-.748 0-2.363.45-2.812 2.25l-.563 3.937h1.969l.562-2.813c0-.376.281-1.124 1.406-1.124zm0 0l-.281 2.25H9.469l-.282 1.687H21zM6.094 17.063l-.563 2.25h9.844c.748 0 2.363-.45 2.812-2.25l.563-3.938h-1.969l-.562 2.812c0 .377-.282 1.126-1.407 1.126zm0 0l.281-2.25h8.156l.281-1.688H3z");
}

</style>
