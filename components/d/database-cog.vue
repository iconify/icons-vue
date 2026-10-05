<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmd0vqb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:database-cog" /></template>
<style>
.fmd0vqb4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 4C19 5.1046 15.4184 6 11 6C6.5816 6 3 5.1046 3 4C3 2.8954 6.5816 2 11 2C15.4184 2 19 2.8954 19 4ZM3 4L3 20C3 20.9319 5.5495 21.715 9 21.937M19 10L19 4M3 12C3 12.9319 5.5495 13.715 9 13.937M19.6667 18C19.6667 19.4728 18.4728 20.6667 17 20.6667C15.5272 20.6667 14.3333 19.4728 14.3333 18C14.3333 16.5272 15.5272 15.3333 17 15.3333C18.4728 15.3333 19.6667 16.5272 19.6667 18ZM20.5417 18L21 18M19.5043 20.5043L19.8284 20.8284M17 21.5417L17 22M14.4957 20.5043L14.1716 20.8284M13.4583 18L13 18M14.4957 15.4957L14.1716 15.1716M17 14.4583L17 14M19.5043 15.4957L19.8284 15.1716");
}

</style>
