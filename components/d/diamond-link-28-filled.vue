<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bmz_t4bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-28-filled" /></template>
<style>
.bmz_t4bvf {
  fill: currentColor;
  d: path("M11.459 7.465a9.55 9.55 0 0 1 6.281 2.794c3.743 3.743 3.743 9.811 0 13.555l-1.086 1.088a3.75 3.75 0 0 1-5.304.001l-8.251-8.25a3.75 3.75 0 0 1-.004-5.3l1.09-1.093v-.001A9.6 9.6 0 0 1 6.76 8.422a10.6 10.6 0 0 0-.309 2.516q-.446.33-.851.736l-1.088 1.09a1.75 1.75 0 0 0 0 2.474l8.252 8.251a1.75 1.75 0 0 0 2.475 0l1.086-1.089a7.585 7.585 0 0 0-5.7-12.94a6.6 6.6 0 0 1 .834-1.995m-.106-4.37a3.75 3.75 0 0 1 5.3.005l8.25 8.25a3.75 3.75 0 0 1 0 5.304l-1.091 1.09a9.6 9.6 0 0 1-2.577 1.837c.204-.826.308-1.672.31-2.517q.447-.33.852-.734l1.092-1.09a1.75 1.75 0 0 0 0-2.475l-8.25-8.251a1.75 1.75 0 0 0-2.474-.002L11.67 5.604a7.586 7.586 0 0 0 5.7 12.939a6.5 6.5 0 0 1-.833 1.994a9.55 9.55 0 0 1-6.28-2.793c-3.743-3.743-3.743-9.812 0-13.556z");
}

</style>
