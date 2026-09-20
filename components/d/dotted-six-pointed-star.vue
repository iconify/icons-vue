<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="x335tacuh"/><path class="xw172ybqy"/><circle class="cfzmzllkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:dotted-six-pointed-star" /></template>
<style>
.cfzmzllkb {
  cx: 18px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.x335tacuh {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M18 34.156c-1.011 0-1.928-.588-2.516-1.614L3.811 12.168c-.602-1.05-.66-2.149-.159-3.014c.473-.816 1.363-1.284 2.441-1.284h24.816c1.09 0 1.978.473 2.438 1.296c.485.869.396 1.961-.242 2.997l-12.63 20.468c-.597.969-1.499 1.525-2.475 1.525M6.524 10.87l11.485 20.044l12.365-20.038z");
}

.xw172ybqy {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M30.909 27.5H6.093c-1.079 0-1.968-.469-2.441-1.285c-.501-.865-.443-1.963.159-3.013L15.484 2.829c.589-1.027 1.505-1.615 2.516-1.615c.976 0 1.878.557 2.476 1.527l12.63 20.466c.639 1.035.728 2.127.242 2.996c-.46.824-1.349 1.297-2.439 1.297M6.528 24.493l23.85.007L18.009 4.457z");
}

</style>
