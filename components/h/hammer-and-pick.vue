<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<defs><path id="SVGvyaiueua" class="ih4g54bph"/></defs><path class="z-31hrbak"/><use href="#SVGvyaiueua"/><use href="#SVGvyaiueua"/><path class="lx5fwzb2u"/><path class="p3bhb2b-c"/><path class="bbarntbev"/><path class="p6tcuzdyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hammer-and-pick" /></template>
<style>
.bbarntbev {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M3.415 7.657a2 2 0 0 1 0-2.829l1.414-1.414a2 2 0 0 1 2.828 2.829L6.243 7.657a2 2 0 0 1-2.828 0");
}

.ih4g54bph {
  fill: var(--svg-color--d67909, #d67909);
  d: path("M32.585 7.657a2 2 0 0 0 0-2.829l-1.414-1.414a2 2 0 0 0-2.828 2.829l1.414 1.414a2 2 0 0 0 2.828 0");
}

.lx5fwzb2u {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M35.789 13.424c-.252-1.765-.375-4.354-3.204-7.182l-.707-.708l-4.949-4.95a2 2 0 0 0-2.828 0L20.565 4.12a2 2 0 0 0 0 2.829l6.364 6.364l2.121 2.121l1.414 1.414c1.027 1.027 3.314 3.315 4.718 1.911c.773-.772.961-2.86.607-5.335");
}

.p3bhb2b-c {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M29.185 33.279c1.166 1.166 3.022 1.221 4.121.121s1.045-2.955-.121-4.121L9.921 6.014C8.754 4.847 6.899 4.792 5.8 5.893c-1.101 1.1-1.046 2.955.121 4.121z");
}

.p6tcuzdyv {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M4.122 15.436c.78.78 2.047.78 2.828 0l8.485-8.485a2 2 0 0 0 0-2.829L11.899.587a2 2 0 0 0-2.828 0L.586 9.071a2 2 0 0 0 0 2.828z");
}

.z-31hrbak {
  fill: var(--svg-color--d67909, #d67909);
  d: path("M6.814 33.279c-1.166 1.166-3.021 1.221-4.121.121s-1.045-2.955.121-4.121L26.079 6.014c1.167-1.167 3.021-1.221 4.121-.121s1.046 2.955-.121 4.121z");
}

</style>
