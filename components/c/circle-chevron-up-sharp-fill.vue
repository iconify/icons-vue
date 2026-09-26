<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omd6vzz8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-up-sharp-fill" /></template>
<style>
.omd6vzz8h {
  fill: currentColor;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM8.4142 15L12 11.4142L15.5858 15L17 13.5858L12.7071 9.2929C12.3166 8.9024 11.6834 8.9024 11.2929 9.2929L7 13.5858L8.4142 15Z");
}

</style>
