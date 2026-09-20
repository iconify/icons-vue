<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t-8b34b6v"/><path class="ienbtuwjw"/><path class="lz3ud2-0r"/><path class="odkwujr8s"/><path class="rtnbgacnf"/><path class="dq6-7ccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fish" /></template>
<style>
.dq6-7ccsd {
  fill: var(--svg-color--269, #269);
  d: path("M15.08 29.98a.997.997 0 0 1-.885-1.463c1.585-3.034 2.218-5.768.154-9.243a1 1 0 0 1 1.72-1.022c2.693 4.535 1.46 8.202-.102 11.191a1 1 0 0 1-.887.537");
}

.ienbtuwjw {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M9.021 14.384c0-3.046 1.497-6.093 3.02-6.093c4.569 0 13.322 4.823 14.845 12.439S9.021 14.384 9.021 14.384m4.854 18.278c1.523 1.523 4.57 3.047 7.617 3.047s-3.111-4.189-1.523-6.092c2.18-2.617-6.094 3.045-6.094 3.045");
}

.lz3ud2-0r {
  d: path("M2.071 28.727c.761-2.285.19-3.935-1.143-5.584c-1.333-1.651 3.872-1.904 5.585.381s5.713 6.281 2.158 6.22c-3.553-.065-6.6-1.017-6.6-1.017");
}

.odkwujr8s {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M.168 23.488c.959.874 7.223 4.309 7.165 5.137s-2.279-.088-3.105-.279c-1.485-.342-1.905-.598-2.317-.526c-.84.321-.554 1.201-.242 1.704c1.498 2.61 7.286 4.662 12.16 4.662c8.412 0 16.802-7.615 16.802-10.662c0-3.046-9.345-10.663-17.757-10.663C4.483 12.86.18 18.922.168 23.488");
}

.rtnbgacnf {
  d: path("M7 17a2 2 0 1 1 .001 3.999A2 2 0 0 1 7 17");
}

.t-8b34b6v {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M32.153 24c0-1 1.523-6.212 3.047-7.735c1.522-1.523 0-3.166-1.523-3.166c-3.405 0-9.139 6.901-9.139 10.901c0 5 5.733 10.424 9.139 10.424c1.523 0 3.046-1.404 1.523-2.928C33.677 29.974 32.153 26 32.153 24");
}

</style>
