<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="zpmtr0f-y"><path class="zonlfdbma"/><path class="t5ip10b2m"/></g><path class="nt5liej9g"/><path class="aqr71ub2q"/><path class="b9g2lty8l"/><path class="g-pyih6os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:aerial-tramway" /></template>
<style>
.aqr71ub2q {
  fill: var(--svg-color--ad9b33, #ad9b33);
  d: path("M22.5 20.431h-3.148c-.215 0-.398.265-.398.585v38.34c0 .15 5.75.23 11.871.238c-9.44-10.687-8.224-25.476-8.325-39.16");
}

.b9g2lty8l {
  fill: var(--svg-color--9a8831, #9a8831);
  d: path("M26.298 42.14v17.346c0 .146 11.611.146 11.611 0V42.139a.3.3 0 0 0-.047-.18l-.006-.008l-.004-.006c-.027-.037-.066-.07-.117-.07H26.473c-.095 0-.175.122-.175.265");
}

.g-pyih6os {
  fill: var(--svg-color--243438, #243438);
  d: path("M20.456 27.66v18.745c0 .155.068.28.15.28h9.626c.082 0 .146-.125.146-.28V27.66a.44.44 0 0 0-.037-.195l-.004-.008l-.006-.006c-.021-.043-.057-.078-.1-.078h-9.626c-.081 0-.149.131-.149.287m13.073-.164v18.745c0 .156.068.28.148.28h9.628c.082 0 .148-.124.148-.28V27.496a.44.44 0 0 0-.039-.195l-.006-.008l-.004-.006c-.021-.043-.057-.078-.1-.078h-9.628c-.078 0-.147.131-.147.287");
}

.nt5liej9g {
  fill: var(--svg-color--ceba35, #ceba35);
  d: path("M18.954 21.02v38.34c0 .32 26.299.32 26.299 0V21.02a.7.7 0 0 0-.105-.398l-.001-.001s-.001-.012-.014-.02a.33.33 0 0 0-.267-.158H19.36c-.214 0-.397.265-.397.586");
}

.t5ip10b2m {
  d: path("m31.88 10.563l-6.993 6.993l6.993 6.991l6.991-6.991zm0 11.213l-4.22-4.22l4.22-4.222l4.22 4.222z");
}

.zonlfdbma {
  d: path("M63.795 20.499C42.528 13.662 21.26 6.833 0 0v3.255q31.89 10.246 63.795 20.494z");
}

.zpmtr0f-y {
  fill: var(--svg-color--243438, #243438);
}

</style>
