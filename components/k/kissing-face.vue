<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="myjh1nkvr"/><path class="g-iuspmhq"/><ellipse class="uhn41ol4b"/><ellipse class="vluco5bua"/><ellipse class="xpc0c1boh"/><ellipse class="bkczvqb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:kissing-face" /></template>
<style>
.bkczvqb_i {
  cx: 45.17px;
  cy: 28.33px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.184px;
  ry: 5.072px;
}

.g-iuspmhq {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M45.729 45.45c-.62-1.451-1.949-2.19-3.949-2.19c-1.56 0-3.252.45-4.49.776l-.723.187c-.318.078-1.969 1.01-1.859 1.904l.193.722h.668c.109 0 .228-.016.365-.049l.602-.15c1.355-.341 2.632-.66 3.964-.662c.781 0 1.454.302 1.988.899c.439.483.369.771.35.864c-.122.49-.884 1.078-1.909 1.468c-.017.006-1.584.651-1.654 1.565l.051.62l.416.236c2.311 1.324 2.264 2.181 1.965 2.781c-.33.656-1.269.799-2 .799a7.9 7.9 0 0 1-2.75-.539l-.425-.081c-.803 0-2.095.966-2.236 1.666l-.07.708l.569.238a8 8 0 0 0 3.116.624c1.886 0 3.811-.659 5.414-1.855c1.422-1.062 1.701-2.17 1.689-2.913c-.02-.934-.503-1.872-1.383-2.714c2.216-1.326 2.924-2.968 2.098-4.904");
}

.myjh1nkvr {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.614 31.811c0 17.566-14.239 31.809-31.809 31.809S0 49.377 0 31.811C0 14.241 14.235 0 31.805 0s31.809 14.241 31.809 31.811");
}

.uhn41ol4b {
  cx: 23.287px;
  cy: 28.33px;
  fill: var(--svg-color--fff, #fff);
  rx: 6.465px;
  ry: 9.684px;
}

.vluco5bua {
  cx: 23.289px;
  cy: 28.33px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.184px;
  ry: 5.072px;
}

.xpc0c1boh {
  cx: 45.16px;
  cy: 28.33px;
  fill: var(--svg-color--fff, #fff);
  rx: 6.465px;
  ry: 9.684px;
}

</style>
