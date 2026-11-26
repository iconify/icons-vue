<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vse50q3in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-operation-fill" /></template>
<style>
.vse50q3in {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4L18.9972 4C20.3986 4 21.5864 4.7064 22.2925 5.7327C22.9986 6.7589 23.2339 8.1208 22.7331 9.4296L19.6717 17.4296C19.0793 18.9777 17.5934 20 15.9359 20L8.0641 20C6.4066 20 4.9207 18.9777 4.3283 17.4296L1.2669 9.4296C0.7661 8.1208 1.0014 6.7589 1.7075 5.7327C2.4136 4.7064 3.6014 4 5.0028 4Z");
}

</style>
