<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="obihunb8y"/><circle class="unrimruze"/><circle class="zxow_e3qi"/><path class="dqd67wjbd"/><path class="fnjlcodwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:anxious-face-with-sweat" /></template>
<style>
.dqd67wjbd {
  fill: currentColor;
  d: path("M26.992 19.58c.541-.469-.971-2.061-1.414-1.674a14.23 14.23 0 0 1-11.693 3.133c-.578-.113-1.088 2.021-.385 2.156a16.42 16.42 0 0 0 13.492-3.615");
}

.fnjlcodwy {
  fill: currentColor;
  d: path("M62 18.535c0-6.848-6.371-13.533-6.371-13.533s-1.819 1.919-3.515 4.742A29.9 29.9 0 0 0 32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30c0-3.112-.475-6.114-1.354-8.938c.83-1.128 1.355-2.633 1.354-4.527M32 59.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5c7.31 0 13.958 2.872 18.888 7.541c-.932 1.992-1.632 4.23-1.632 6.494c0 .891.116 1.695.324 2.417a14.2 14.2 0 0 1-11.158-3.198c-.443-.389-1.955 1.205-1.412 1.674a16.42 16.42 0 0 0 13.492 3.615c.026-.005.04-.031.063-.041c1.865 2.604 5.352 3.226 7.989 1.859c.614 2.278.946 4.67.946 7.139c0 15.164-12.337 27.5-27.5 27.5");
}

.obihunb8y {
  fill: currentColor;
  d: path("M32 39.828a8.313 8.313 0 1 0 8.313 8.313A8.31 8.31 0 0 0 32 39.828m-5.816 4.953a6.717 6.717 0 0 1 11.634-.004z");
}

.unrimruze {
  cx: 43.5px;
  cy: 33px;
  r: 4.5px;
  fill: currentColor;
}

.zxow_e3qi {
  cx: 20.5px;
  cy: 33px;
  r: 4.5px;
  fill: currentColor;
}

</style>
