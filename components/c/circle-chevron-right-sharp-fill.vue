<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-r8iu1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-right-sharp-fill" /></template>
<style>
.cb-r8iu1u {
  fill: currentColor;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM9 8.4142L12.5858 12L9 15.5858L10.4142 17L14.7071 12.7071C15.0976 12.3166 15.0976 11.6834 14.7071 11.2929L10.4142 7L9 8.4142Z");
}

</style>
