<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a578usmfc"/><path class="fcr9zqb9w"/><path class="c1r473bqp"/><path class="s3lmx6dpe"/><path class="jccd2bqjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eng" /></template>
<style>
.a578usmfc {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.972 3l7.779 4.464v8.928l-7.78 4.464l-7.722-4.464V7.464z");
}

.c1r473bqp {
  fill: var(--svg-color--21b1f8, #21b1f8);
  d: path("m12 12.078l4.133-2.367v4.532L12 16.811z");
}

.fcr9zqb9w {
  fill: var(--svg-color--065198, #065198);
  d: path("M11.968 11.876L7.866 9.52v4.509l4.102 2.64z");
}

.ft5dv1b6b {
  fill: none;
}

.jccd2bqjs {
  fill: var(--svg-color--0c0e15, #0c0e15);
  d: path("M3.945 7.163a.274.274 0 0 0 .1.375l7.684 4.474v8.714a.274.274 0 1 0 .548 0v-8.714l7.674-4.456a.274.274 0 1 0-.275-.473l-7.673 4.454L4.32 7.065a.274.274 0 0 0-.375.098M12 5.274a.44.44 0 1 0 0-.882a.44.44 0 0 0 0 .882m0 1.207a.44.44 0 1 0 0-.881a.44.44 0 0 0 0 .881m-5.034 8.51a.44.44 0 1 0 0-.881a.44.44 0 0 0 0 .881m-1.208.756a.44.44 0 1 0 0-.881a.44.44 0 0 0 0 .881m11.358-.756a.44.44 0 1 1 0-.881a.44.44 0 0 1 0 .881m1.209.756a.44.44 0 1 1 0-.882a.44.44 0 0 1 0 .882");
}

.s3lmx6dpe {
  fill: var(--svg-color--e82e9d, #e82e9d);
  d: path("m12 6.971l4.138 2.566l-4.139 2.299l-4.097-2.298z");
}

</style>
