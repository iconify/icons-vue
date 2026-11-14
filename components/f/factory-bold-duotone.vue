<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoq0vobwr"/><path class="egy4842al"/><path class="fl-711bme"/><path class="hvd9589tj"/><path class="yvlcebcfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:factory-bold-duotone" /></template>
<style>
.aoq0vobwr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 22V4.2C3 3.1629 3 2.6444 3.3222 2.3222C3.6444 2 4.1629 2 5.2 2H5.8C6.8371 2 7.3556 2 7.6778 2.3222C8 2.6444 8 3.1629 8 4.2V11.7C8 12.0771 8 12.2657 8.0949 12.3142C8.1899 12.3627 8.3427 12.2522 8.6483 12.0312L12.8793 8.9719C13.6433 8.4195 14.0253 8.1432 14.2626 8.2645C14.5 8.3858 14.5 8.8572 14.5 9.8V11.7C14.5 12.0771 14.5 12.2657 14.5949 12.3142C14.6899 12.3627 14.8427 12.2522 15.1483 12.0312L19.3793 8.9719C20.1433 8.4195 20.5253 8.1432 20.7626 8.2645C21 8.3858 21 8.8572 21 9.8V22H3Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.egy4842al {
  fill: currentColor;
  d: path("M22 21.25C22.4142 21.25 22.75 21.5858 22.75 22C22.75 22.4142 22.4142 22.75 22 22.75H2C1.58579 22.75 1.25 22.4142 1.25 22C1.25 21.5858 1.58579 21.25 2 21.25H22Z");
}

.fl-711bme {
  fill: currentColor;
  d: path("M8.5 16.75C8.91421 16.75 9.25 17.0858 9.25 17.5C9.25 17.9142 8.91421 18.25 8.5 18.25H7C6.58579 18.25 6.25 17.9142 6.25 17.5C6.25 17.0858 6.58579 16.75 7 16.75H8.5Z");
}

.hvd9589tj {
  fill: currentColor;
  d: path("M12.75 16.75C13.1642 16.75 13.5 17.0858 13.5 17.5C13.5 17.9142 13.1642 18.25 12.75 18.25H11.25C10.8358 18.25 10.5 17.9142 10.5 17.5C10.5 17.0858 10.8358 16.75 11.25 16.75H12.75Z");
}

.yvlcebcfg {
  fill: currentColor;
  d: path("M17 16.75C17.4142 16.75 17.75 17.0858 17.75 17.5C17.75 17.9142 17.4142 18.25 17 18.25H15.5C15.0858 18.25 14.75 17.9142 14.75 17.5C14.75 17.0858 15.0858 16.75 15.5 16.75H17Z");
}

</style>
