<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e8dh5bche"/><path class="zs7ix-wly"/><path class="p6z-p2b3g"/><path class="iwf1orrtp"/><path class="rwxq5w_ah"/><path class="e509rqa8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:floppy-disk" /></template>
<style>
.e509rqa8z {
  fill: var(--svg-color--f15744, #f15744);
  d: path("M12 54h40v8H12zm5-18h30v2H17zm0 6h30v2H17zm0 6h30v2H17z");
}

.e8dh5bche {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m61.3 9.3l-6.6-6.6c-.4-.4-1.2-.7-1.7-.7H9v4H5V2H3c-.5 0-1 .5-1 1v58c0 .5.5 1 1 1h58c.5 0 1-.5 1-1V11c0-.6-.3-1.3-.7-1.7");
}

.iwf1orrtp {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M36 6h10v16H36z");
}

.p6z-p2b3g {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("M18 2v20c0 1.1.9 2 2 2h30c1.1 0 2-.9 2-2V2z");
}

.rwxq5w_ah {
  fill: var(--svg-color--fff, #fff);
  d: path("M59 56c0-.6-.5-1-1-1h-2c-.5 0-1 .4-1 1v2c0 .5.5 1 1 1h2c.5 0 1-.5 1-1z");
}

.zs7ix-wly {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 62V34c0-1.1.9-2 2-2h36c1.1 0 2 .9 2 2v28z");
}

</style>
