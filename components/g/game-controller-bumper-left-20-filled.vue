<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubpebfbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-bumper-left-20-filled" /></template>
<style>
.ubpebfbzy {
  fill: currentColor;
  d: path("M9.2 5.172a24.2 24.2 0 0 1 4.93-.049c.563.055 1.069.32 1.45.707l1.225 1.244a4 4 0 0 1 .909 4.174l-.767 2.107A2.5 2.5 0 0 1 14.597 15H4.044a2 2 0 0 1-1.991-2.184l.339-3.67c.08-.875.487-1.772 1.312-2.279C5.313 5.88 7.32 5.39 9.2 5.172M10.5 8a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h1c.191 0 .669.02 1.088-.13c.223-.08.46-.218.64-.454c.182-.24.272-.54.272-.886c0-.531-.23-.92-.535-1.17l.033-.043c.152-.225.236-.498.236-.813c0-.294-.06-.558-.186-.782a1.3 1.3 0 0 0-.498-.494C12.185 8.023 11.765 8 11.5 8zm-4 0a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H7V8.5a.5.5 0 0 0-.5-.5m5.5 3c.063 0 .204.032.32.121c.094.073.18.19.18.41c0 .166-.041.243-.07.28a.4.4 0 0 1-.18.118c-.217.078-.49.071-.75.071H11v-1zm-.5-2c.234 0 .432.028.56.1q.078.044.116.11a.6.6 0 0 1 .058.294a.43.43 0 0 1-.063.252a.4.4 0 0 1-.165.136A1.2 1.2 0 0 1 11.5 10H11V9z");
}

</style>
