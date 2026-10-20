<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abt3ywbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drafting-compass-sharp" /></template>
<style>
.abt3ywbrv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 1L12 4M11.1984 7.8323L4.7379 22.5992M12.8016 7.8323L19.2621 22.5992M14 6C14 7.1046 13.1046 8 12 8C10.8954 8 10 7.1046 10 6C10 4.8954 10.8954 4 12 4C13.1046 4 14 4.8954 14 6ZM21.25 13.6538L21 13.9373C18.722 16.5203 15.444 18 12 18C8.556 18 5.278 16.5203 3 13.9373L2.75 13.6538");
}

</style>
